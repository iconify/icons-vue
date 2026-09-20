<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do1c-8sjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="do1c-8sjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:poweroff" /></template>
