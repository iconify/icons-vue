<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgsklfbyu.css';
import '../../css/d/d516lezif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rgsklfbyu"/><path class="d516lezif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-graph" /></template>
