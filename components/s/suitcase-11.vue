<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo1bv_b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="oo1bv_b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:suitcase-11" /></template>
