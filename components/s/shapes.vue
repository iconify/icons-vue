<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8pz_1b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l8pz_1b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:shapes" /></template>
