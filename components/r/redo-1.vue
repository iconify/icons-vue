<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jivb_cbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jivb_cbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:redo-1" /></template>
