<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grv7j-bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="grv7j-bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:screen-normal" /></template>
