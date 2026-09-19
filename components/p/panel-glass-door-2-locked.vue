<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo9spyvda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo9spyvda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door-2-locked" /></template>
