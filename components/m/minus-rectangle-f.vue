<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dri3zmbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="dri3zmbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:minus-rectangle-f" /></template>
