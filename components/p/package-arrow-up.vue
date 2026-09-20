<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcnv909_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcnv909_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-arrow-up" /></template>
