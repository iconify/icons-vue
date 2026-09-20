<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkhsd8blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lkhsd8blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-skull" /></template>
