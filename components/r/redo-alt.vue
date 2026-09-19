<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2d88b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ve2d88b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:redo-alt" /></template>
