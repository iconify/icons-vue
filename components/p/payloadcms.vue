<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux66g_b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ux66g_b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:payloadcms" /></template>
