<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykv5j8bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ykv5j8bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-4-flat" /></template>
