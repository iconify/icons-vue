<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4v_z4_rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4v_z4_rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speed-up-line" /></template>
