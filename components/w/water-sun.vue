<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcqr5ubrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcqr5ubrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:water-sun" /></template>
