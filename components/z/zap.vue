<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_gzhippd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="e_gzhippd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zap" /></template>
