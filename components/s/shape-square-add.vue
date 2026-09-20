<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu3pwt-uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu3pwt-uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape-square-add" /></template>
