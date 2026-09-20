<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw6-f9bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw6-f9bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:palette-swatch-variant" /></template>
