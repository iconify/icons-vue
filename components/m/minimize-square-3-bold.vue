<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivgsmkbsz.css';
import '../../css/u/uto2arb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgsmkbsz"/><path clip-rule="evenodd" class="uto2arb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-3-bold" /></template>
