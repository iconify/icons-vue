<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wflgxsbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wflgxsbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:skip-back" /></template>
