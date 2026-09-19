<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re149_bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="re149_bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:phone-number" /></template>
