<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfr121xds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="qfr121xds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:question" /></template>
