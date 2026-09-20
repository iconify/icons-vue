<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnnky2uik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rnnky2uik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bars-weaker-signal" /></template>
