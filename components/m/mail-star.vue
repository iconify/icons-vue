<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_k__0-_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_k__0-_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-star" /></template>
