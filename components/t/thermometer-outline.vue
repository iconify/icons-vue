<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyjboy1lu.css';
import '../../css/w/w72z5bcvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyjboy1lu"/><path clip-rule="evenodd" class="w72z5bcvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:thermometer-outline" /></template>
