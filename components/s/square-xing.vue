<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9w0hsbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t9w0hsbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-xing" /></template>
