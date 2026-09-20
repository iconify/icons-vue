<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2dbv3b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2dbv3b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wrench-line" /></template>
