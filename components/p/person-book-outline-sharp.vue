<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6n28ovog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-book-outline-sharp" /></template>
<style>
.e6n28ovog {
  fill: currentColor;
  d: path("M12 17.385q-1.554 0-3.021.514q-1.467.515-2.748 1.582V20H17.75v-.52q-1.242-1.066-2.71-1.581T12 17.385m3.225-.475q1.5.525 2.775 1.475V4H6v14.385q1.275-.95 2.775-1.475T12 16.385t3.225.525m-4.634-4.424Q10 11.894 10 11.077t.591-1.409q.592-.591 1.409-.591t1.409.591q.591.592.591 1.409t-.591 1.409t-1.409.591t-1.409-.591M5 21V3h14v18zm9.129-7.794q.871-.871.871-2.129t-.871-2.129T12 8.077t-2.129.871T9 11.077t.871 2.129t2.129.871t2.129-.871M12 11.077");
}

</style>
