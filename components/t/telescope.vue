<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzh6aom-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="rzh6aom-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:telescope" /></template>
