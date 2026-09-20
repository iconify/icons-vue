<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpy7--blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpy7--blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:smile" /></template>
