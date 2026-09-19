<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7fz9o70k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="h7fz9o70k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:ubuntu" /></template>
