<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24cc3bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i24cc3bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tape-measure" /></template>
