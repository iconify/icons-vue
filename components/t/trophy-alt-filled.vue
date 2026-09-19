<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j85fdy7uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j85fdy7uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trophy-alt-filled" /></template>
