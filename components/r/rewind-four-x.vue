<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegyyab8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oegyyab8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rewind-four-x" /></template>
