<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwwuyc43w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwwuyc43w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:view-grid" /></template>
