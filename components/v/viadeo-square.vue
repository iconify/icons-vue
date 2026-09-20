<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1b5zwbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e1b5zwbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:viadeo-square" /></template>
