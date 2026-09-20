<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llnjf5bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="llnjf5bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:qq" /></template>
