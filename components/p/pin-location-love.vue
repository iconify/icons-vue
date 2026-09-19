<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyn838j8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fyn838j8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pin-location-love" /></template>
