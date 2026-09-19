<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc2ta6dqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc2ta6dqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:remove-x-cross" /></template>
