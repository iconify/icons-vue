<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxf2sccbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qxf2sccbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-taxi" /></template>
