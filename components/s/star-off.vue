<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9hfwhy9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j9hfwhy9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:star-off" /></template>
