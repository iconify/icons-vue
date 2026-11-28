<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxbd9gbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxbd9gbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tv-check" /></template>
