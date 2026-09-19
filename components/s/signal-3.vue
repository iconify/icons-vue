<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgihh71tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sgihh71tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-3" /></template>
