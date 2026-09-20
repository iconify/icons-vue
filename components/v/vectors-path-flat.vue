<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf54abxwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gf54abxwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:vectors-path-flat" /></template>
