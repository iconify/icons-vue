<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqhp__bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hqhp__bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paragraph-solid" /></template>
