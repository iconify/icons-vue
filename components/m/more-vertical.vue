<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16mtllzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m16mtllzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:more-vertical" /></template>
