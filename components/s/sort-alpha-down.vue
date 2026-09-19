<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzy-a35gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qzy-a35gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:sort-alpha-down" /></template>
