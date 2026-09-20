<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zloyalpnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zloyalpnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mist-line" /></template>
