<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0l-facaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0l-facaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-off-outline" /></template>
