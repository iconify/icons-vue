<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_beh2el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nm_beh2el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pause" /></template>
