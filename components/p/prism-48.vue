<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lymkpobns.css';
import '../../css/x/xfeis42ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lymkpobns"/><path class="xfeis42ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:prism-48" /></template>
