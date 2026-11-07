<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3oz6trwf.css';
import '../../css/d/dmz5tfbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3oz6trwf"/><path class="dmz5tfbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:syringe-bold" /></template>
