<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxt49qctb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uxt49qctb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-zoom-out" /></template>
