<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn0goxnbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn0goxnbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:unavailable-light" /></template>
