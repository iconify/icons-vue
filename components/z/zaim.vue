<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcrotsbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcrotsbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zaim" /></template>
