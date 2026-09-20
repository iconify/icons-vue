<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b74gpab8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b74gpab8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sun" /></template>
