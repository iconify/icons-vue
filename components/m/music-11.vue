<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnafimb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="xnafimb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:music-11" /></template>
