<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z18-h610e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z18-h610e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nodejs" /></template>
