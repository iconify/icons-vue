<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq-j7ccmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bq-j7ccmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:street-2" /></template>
