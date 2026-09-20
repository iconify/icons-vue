<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obg18lb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obg18lb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-in-ar" /></template>
