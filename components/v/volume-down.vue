<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7o-o3clb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1280};
const content = `<path class="i7o-o3clb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:volume-down" /></template>
