<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0h54ux4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0h54ux4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-upload-corner-fill-round" /></template>
