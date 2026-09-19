<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx61tsb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="mx61tsb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:signal-1" /></template>
