<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvfovab-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvfovab-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slickdeals-dark" /></template>
