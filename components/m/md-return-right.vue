<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w46o3ib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w46o3ib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-return-right" /></template>
