<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenee3cws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zenee3cws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape-add-outline" /></template>
