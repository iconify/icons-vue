<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_pr8ov3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="u_pr8ov3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-shinto-11" /></template>
