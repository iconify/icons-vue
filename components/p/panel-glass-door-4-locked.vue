<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-ni3xu8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ni3xu8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door-4-locked" /></template>
