<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d254ld3ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d254ld3ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:railway-track-askew" /></template>
