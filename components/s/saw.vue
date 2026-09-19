<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxyxo_byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="jxyxo_byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:saw" /></template>
