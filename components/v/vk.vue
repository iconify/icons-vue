<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cem9iobou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1952,"height":1280};
const content = `<path class="cem9iobou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:vk" /></template>
