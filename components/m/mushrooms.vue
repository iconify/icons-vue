<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih-vw5bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="ih-vw5bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mushrooms" /></template>
