<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdrtjpb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zdrtjpb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:police-jp-15" /></template>
