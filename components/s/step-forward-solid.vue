<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb0r06b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fb0r06b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:step-forward-solid" /></template>
