<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc1qm-bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc1qm-bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:radio" /></template>
