<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpj3_ybqz.css';
import '../../css/v/v_f07jpah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kpj3_ybqz"/><path class="v_f07jpah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seaweed-20-bold" /></template>
