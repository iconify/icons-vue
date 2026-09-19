<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcj6hkb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcj6hkb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:square-3-stack-3d" /></template>
