<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnmr3zbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnmr3zbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-play" /></template>
