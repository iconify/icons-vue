<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/louj8cble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="louj8cble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sound-mute" /></template>
