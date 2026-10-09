<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0hsllbzz.css';
import '../../css/h/hsyyodqzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0hsllbzz"/><path class="hsyyodqzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pliers-48-bold" /></template>
