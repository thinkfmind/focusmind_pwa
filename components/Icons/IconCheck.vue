<template>
    <svg width="14" height="12" viewBox="0 0 14 12" fill="none" xmlns="http://www.w3.org/2000/svg" :style="csStyle">
        <path d="M10.3485 1.3488L10.3485 1.34883L5.33873 8.14418L2.9745 6.40117C2.9745 6.40116 2.97449 6.40116 2.97448 6.40115C2.51755 6.06426 1.87418 6.1617 1.53735 6.61848L1.53733 6.6185C1.20045 7.0754 1.29779 7.71883 1.75468 8.05567L2.05139 7.65322L1.75469 8.05567L4.94613 10.4085C4.94615 10.4085 4.94617 10.4085 4.94619 10.4086C5.40316 10.7455 6.04677 10.6477 6.38336 10.1912L12.003 2.56864C12.3399 2.11172 12.2425 1.46829 11.7857 1.13147C11.3288 0.794581 10.6854 0.891948 10.3485 1.3488Z" :fill="color" :stroke="color"/>
    </svg>

</template>

<style scoped>
    svg{
        height: 1em;
        vertical-align: middle;
        line-height: 1em;
    }
</style>
<script>
export default {
    props:{
        'cs-style':{
            type:String,
            default:''
        },
        'color':{
            type:String,
            default:'#B38A58'
        }
    }
}
</script>
