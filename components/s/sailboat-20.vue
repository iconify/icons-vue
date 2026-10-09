<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1weu1kyu.css';
import '../../css/c/cjj4u9psh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h1weu1kyu"/><path class="cjj4u9psh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sailboat-20" /></template>
