<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj3zoshwv.css';
import '../../css/l/l8fg_nb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jj3zoshwv"/><path class="l8fg_nb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-out-20-bold" /></template>
