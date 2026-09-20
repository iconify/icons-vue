<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5jsz3bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c5jsz3bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-below-text" /></template>
