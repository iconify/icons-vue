<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7xy_cbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7xy_cbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paragraph-spacing" /></template>
