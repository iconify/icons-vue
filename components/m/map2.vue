<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg6-sxb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6-sxb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map2" /></template>
