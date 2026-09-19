<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y78v_dbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="y78v_dbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:music" /></template>
