<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv4fs4baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:travel-luggage-and-bags-sharp" /></template>
<style>
.qv4fs4baz {
  fill: currentColor;
  d: path("M10.904 7h2.192V4.808h-2.192zm-2.02 4.828Q7.382 11.271 6 10.412V7h3.904V3.808h4.192V7H18v3.412q-1.38.86-2.884 1.416q-1.504.557-3.116.557t-3.116-.557M7.616 21v-1H6v-8.415q1.285.734 2.657 1.21q1.372.474 2.843.578v1.012h1v-1.012q1.471-.104 2.843-.579q1.373-.475 2.657-1.21V20h-1.616v1h-1v-1H8.616v1z");
}

</style>
