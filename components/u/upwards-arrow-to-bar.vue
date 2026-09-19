<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx4y6cc8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="qx4y6cc8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:upwards-arrow-to-bar" /></template>
