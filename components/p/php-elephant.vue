<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1hlh30_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1hlh30_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:php-elephant" /></template>
