<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeks_mbgq.css';
import '../../css/m/m7hm-zmpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aeks_mbgq"/><path class="m7hm-zmpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:octoface-16" /></template>
