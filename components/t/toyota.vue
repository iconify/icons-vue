<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huv7wf-bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huv7wf-bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:toyota" /></template>
