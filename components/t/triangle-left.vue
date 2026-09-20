<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9hgbnx1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="r9hgbnx1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-left" /></template>
