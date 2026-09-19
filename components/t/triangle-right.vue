<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1fybybou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="n1fybybou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:triangle-right" /></template>
