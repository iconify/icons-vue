<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu63zhw-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hu63zhw-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:pinterest-p" /></template>
