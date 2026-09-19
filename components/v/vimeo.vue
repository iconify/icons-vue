<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy_j5wugz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xy_j5wugz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:vimeo" /></template>
