<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzrje_bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yzrje_bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:portrait" /></template>
