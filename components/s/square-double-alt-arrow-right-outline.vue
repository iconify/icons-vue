<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3vjmwkjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3vjmwkjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-double-alt-arrow-right-outline" /></template>
