<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7ctc27_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u7ctc27_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock-fill" /></template>
