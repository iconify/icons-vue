<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmtkkfgsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xmtkkfgsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:tag" /></template>
