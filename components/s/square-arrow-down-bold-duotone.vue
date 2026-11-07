<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftxh2yu-e.css';
import '../../css/e/esz28i62g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftxh2yu-e"/><path class="esz28i62g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-down-bold-duotone" /></template>
