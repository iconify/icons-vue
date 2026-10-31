<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-ka6b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-ka6b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-sparkle-corner-fill-round" /></template>
