<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_c61queu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c_c61queu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vest-patches" /></template>
