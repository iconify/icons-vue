<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7-lexb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r7-lexb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:page-break" /></template>
