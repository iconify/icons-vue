<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_zm4_bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_zm4_bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:poker-chip" /></template>
