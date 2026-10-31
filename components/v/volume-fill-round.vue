<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri78dbu8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri78dbu8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-fill-round" /></template>
