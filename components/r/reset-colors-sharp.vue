<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-q6_5bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-colors-sharp" /></template>
<style>
.j-q6_5bni {
  fill: currentColor;
  d: path("m17.27 22.408l-5.158-5.158l4.45-4.45l-1.835-1.834l.688-.708l7.018 6.992zm-3.57-5.37h7.08l-3.53-3.53zM5 20v-1h3.312q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.706 0 4.778 1.584q2.072 1.583 2.843 4.032h-1.036q-.727-2.027-2.504-3.322T12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15h1v5z");
}

</style>
