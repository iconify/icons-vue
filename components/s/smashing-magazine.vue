<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca6smfbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca6smfbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:smashing-magazine" /></template>
