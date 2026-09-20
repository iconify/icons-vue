<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfljk-bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dfljk-bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-shutoff-with-bolt" /></template>
