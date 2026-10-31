<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-2ejcb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-2ejcb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-check-corner-round" /></template>
