<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65hvpbwb.css';
import '../../css/q/q_b498z9b.css';
import '../../css/c/cxf8pnbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g65hvpbwb"/><path class="q_b498z9b"/><path class="cxf8pnbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-sleep-bold" /></template>
