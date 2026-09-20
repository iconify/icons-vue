<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2nef2b2z.css';
import '../../css/f/fru8l0jpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2nef2b2z"/><path class="fru8l0jpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-inbox" /></template>
