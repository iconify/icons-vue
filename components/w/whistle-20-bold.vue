<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtw_wzb8t.css';
import '../../css/g/gseyqnbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qtw_wzb8t"/><path class="gseyqnbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whistle-20-bold" /></template>
