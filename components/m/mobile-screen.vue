<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkvfwp7eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="rkvfwp7eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mobile-screen" /></template>
