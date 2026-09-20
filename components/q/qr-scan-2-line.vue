<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-rv1g-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-rv1g-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qr-scan-2-line" /></template>
