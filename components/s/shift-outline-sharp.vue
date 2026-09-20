<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flhvvpb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shift-outline-sharp" /></template>
<style>
.flhvvpb4i {
  fill: currentColor;
  d: path("M9 20v-7.23H5.115L12 3.576l6.885 9.192H15V20zm1-1h4v-7.23h2.775L12 5.245L7.225 11.77H10zm2-7.23");
}

</style>
