<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc3l9v3wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bc3l9v3wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:megaphone" /></template>
