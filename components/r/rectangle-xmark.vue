<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo7aw631a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo7aw631a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rectangle-xmark" /></template>
