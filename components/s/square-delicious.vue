<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc3_pqumv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="mc3_pqumv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square-delicious" /></template>
