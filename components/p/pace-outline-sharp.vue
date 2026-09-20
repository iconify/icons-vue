<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv9zu9ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pace-outline-sharp" /></template>
<style>
.ytv9zu9ix {
  fill: currentColor;
  d: path("M12 21q-1.868 0-3.51-.708t-2.857-1.924t-1.924-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709t2.859 1.924t1.925 2.857T21 12q0 .675-.094 1.325t-.289 1.275q-.196-.17-.418-.3t-.484-.192q.152-.51.219-1.032Q20 12.554 20 12q0-3.35-2.325-5.675T12 4T6.325 6.325T4 12t2.325 5.675T12 20q1.352 0 2.562-.416q1.21-.415 2.225-1.163q.165.194.353.365q.187.172.418.289q-1.16.91-2.563 1.417Q13.59 21 12 21m6.43-3.717q-.219-.217-.219-.532q0-.314.218-.533T18.96 16t.533.217t.218.532t-.217.533t-.532.218t-.532-.217m-2.784-.93L11.5 12.208V7h1v4.792l3.854 3.854z");
}

</style>
