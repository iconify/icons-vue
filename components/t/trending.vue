<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_d69u3-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_d69u3-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trending" /></template>
