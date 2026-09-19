<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty80_-i1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ty80_-i1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pin-location-delete" /></template>
