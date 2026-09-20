<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxro7nbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxro7nbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:play-duotone" /></template>
