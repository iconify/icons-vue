<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqew88cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjqew88cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:section-plus" /></template>
