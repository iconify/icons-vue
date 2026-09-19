<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilj6i9a_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilj6i9a_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatori" /></template>
