<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xipgem6_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xipgem6_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:overall-reduction" /></template>
