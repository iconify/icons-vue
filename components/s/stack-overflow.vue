<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajvt07bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ajvt07bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:stack-overflow" /></template>
