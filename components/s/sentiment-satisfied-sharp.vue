<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnsio1bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-satisfied-sharp" /></template>
<style>
.pnsio1bro {
  fill: currentColor;
  d: path("M15.312 10.616q.467 0 .789-.327t.322-.793t-.326-.79q-.327-.321-.794-.321t-.789.326t-.322.793t.327.79q.326.322.793.322m-6.615 0q.466 0 .788-.327q.323-.327.323-.793q0-.467-.327-.79q-.327-.321-.793-.321q-.467 0-.789.326q-.322.327-.322.793q0 .467.326.79q.327.322.794.322m5.938 5.48q1.205-.79 1.811-2.096h-.996q-.55.925-1.462 1.463T12 16t-1.987-.537T8.55 14h-.996q.606 1.306 1.81 2.095t2.636.79t2.636-.79m-6.143 4.197q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51T5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709t-3.51-.708");
}

</style>
