<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0-_cdbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0-_cdbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:television-question-mark-fill" /></template>
