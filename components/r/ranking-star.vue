<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk5gs5b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="kk5gs5b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ranking-star" /></template>
