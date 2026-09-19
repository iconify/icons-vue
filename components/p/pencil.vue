<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yym89wbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yym89wbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:pencil" /></template>
