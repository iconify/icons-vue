<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohymefbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohymefbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-previous" /></template>
