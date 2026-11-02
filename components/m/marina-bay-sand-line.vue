<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp5uy7o3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp5uy7o3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:marina-bay-sand-line" /></template>
