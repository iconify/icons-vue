<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp2_fhctv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-book-outline-rounded" /></template>
<style>
.tp2_fhctv {
  fill: currentColor;
  d: path("M12 17.385q-1.554 0-3.021.514q-1.467.515-2.748 1.582q.038.223.211.365q.173.143.385.154h10.327q.212-.012.385-.154t.211-.365q-1.242-1.068-2.71-1.582T12 17.385m3.225-.475q1.5.525 2.775 1.475V4.615q0-.23-.192-.423T17.384 4H6.616q-.231 0-.424.192T6 4.615v13.77q1.275-.95 2.775-1.476T12 16.385t3.225.525m-4.634-4.423Q10 11.894 10 11.077t.591-1.409q.592-.591 1.409-.591t1.409.591q.591.592.591 1.409t-.591 1.409t-1.409.591t-1.409-.591M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616v14.769q0 .69-.462 1.153T17.384 21zm7.513-7.794q.871-.871.871-2.129t-.871-2.129T12 8.077t-2.129.871T9 11.077t.871 2.129t2.129.871t2.129-.871M12 11.077");
}

</style>
