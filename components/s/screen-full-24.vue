<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcjiy60hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcjiy60hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:screen-full-24" /></template>
