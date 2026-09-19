<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9e8i8b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="j9e8i8b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:modx" /></template>
