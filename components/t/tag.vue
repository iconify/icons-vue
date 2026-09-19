<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccub-obgi.css';
import '../../css/z/zbv5-bbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ccub-obgi"/><path class="zbv5-bbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:tag" /></template>
