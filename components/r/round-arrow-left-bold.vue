<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y84yphq7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y84yphq7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-bold" /></template>
