<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx3b7pbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dx3b7pbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rug" /></template>
