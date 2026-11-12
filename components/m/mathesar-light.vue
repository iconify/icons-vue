<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn4oblbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn4oblbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mathesar-light" /></template>
