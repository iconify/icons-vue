<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu88yodte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zu88yodte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:reply-all" /></template>
