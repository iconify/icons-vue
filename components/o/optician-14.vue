<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beljj4eyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="beljj4eyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:optician-14" /></template>
