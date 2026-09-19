<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye9gr2dqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="ye9gr2dqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:shield" /></template>
