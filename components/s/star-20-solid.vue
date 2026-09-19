<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0gng4b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j0gng4b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:star-20-solid" /></template>
