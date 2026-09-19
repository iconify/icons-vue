<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2u-wxb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a2u-wxb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pound-sign" /></template>
