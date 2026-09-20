<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri4agxb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri4agxb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scan-fill" /></template>
