<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca9mp9bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ca9mp9bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vimeo-square" /></template>
