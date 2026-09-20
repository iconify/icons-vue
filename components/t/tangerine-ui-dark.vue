<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkkupx0gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkkupx0gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tangerine-ui-dark" /></template>
