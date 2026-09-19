<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwqz4hyhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mwqz4hyhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:screwdriver" /></template>
