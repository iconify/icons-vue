<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6qsnzvxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6qsnzvxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-letter-spacing" /></template>
