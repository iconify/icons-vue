<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_dx56bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s_dx56bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pill-outline" /></template>
