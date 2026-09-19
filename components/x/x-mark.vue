<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfqzyy89q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yfqzyy89q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:x-mark" /></template>
