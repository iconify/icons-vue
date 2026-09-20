<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfv7x8bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfv7x8bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant-subtract" /></template>
