<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yog0jzrzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yog0jzrzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vertical-rotisserie" /></template>
