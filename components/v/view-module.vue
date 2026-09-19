<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcgtlkb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="xcgtlkb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-module" /></template>
