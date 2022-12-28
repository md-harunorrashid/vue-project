<template>
  
    <!-- <h1 class="text-red-500 mt-10 mb-6 text-center font-bold "> {{ msg }}</h1> -->
    <div class="container mx-auto text-center font-bold text-black">
        <h1 class="text-4xl mt-10 text-cyan-500" >Array & Loop</h1>
        <div v-for="course in courses" class="shadow border border-gray-200 p-4 mb-4 mt-10">
            <h1>{{ course.id }}</h1>
            <h2>{{ course.name }}</h2>
            <p>{{ course.description }}</p>

        </div>

        <!-- <button class=" bg-gray-600 bg- py-2 px-6 rounded hover:bg-cyan-700" @click="test">Test</button> -->

        

    </div>
   
</template>





<script>
export default{
    name:'App',
    data(){
        return{
            //msg : 'Welcome to Vue Project',
            courses:[
                {
                    id: 1,
                    name:  'PHP',
                    description: 'PHP is a powerful Programming Language.',
                    price:100,

                },
                {
                    id: 2,
                    name:  'Python',
                    description: 'PHP is a powerful Programming Language.',
                    price:100,

                },
                {
                    id: 3,
                    name:  'JavaScript',
                    description: 'PHP is a powerful Programming Language.',
                    price:100,

                },
                {
                    id: 4,
                    name:  'Vue',
                    description: 'PHP is a powerful Programming Language.',
                    price:100,

                },
                {
                    id: 5,
                    name:  'Tailwind CSS',
                    description: 'PHP is a powerful Programming Language.',
                    price:100,

                },
               // 'PHP','JavaScript','Vue', 'Tailwind CSS'
            ]

        }
    },
    
    // mounted(){
    //     this.test()

    // },
    // methods:{
    //     test(){
    //        // alert('test')
    //        this.msg  = 'Change'
          
    //   }

    // }
};

</script>
