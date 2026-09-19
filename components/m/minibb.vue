<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry_3st_jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ry_3st_jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minibb" /></template>
