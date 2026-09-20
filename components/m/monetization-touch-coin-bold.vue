<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk1yoeo-c.css';
import '../../css/i/i31-_h-xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk1yoeo-c"/><path class="i31-_h-xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monetization-touch-coin-bold" /></template>
