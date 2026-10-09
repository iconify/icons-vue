<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6cl-bwp.css';
import '../../css/x/xollm1waj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dg6cl-bwp"/><path class="xollm1waj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pliers-20" /></template>
