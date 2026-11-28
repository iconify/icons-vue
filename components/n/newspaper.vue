<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtkl190ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtkl190ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:newspaper" /></template>
