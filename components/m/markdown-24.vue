<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dozxz0bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dozxz0bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:markdown-24" /></template>
