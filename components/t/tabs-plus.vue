<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtki3q1-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtki3q1-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tabs-plus" /></template>
