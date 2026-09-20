<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6y8m1bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m6y8m1bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mood-sad-solid" /></template>
