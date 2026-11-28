<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7o95nfdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7o95nfdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartwatch-x" /></template>
