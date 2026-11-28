<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_uv8bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw_uv8bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:octagon-solid" /></template>
