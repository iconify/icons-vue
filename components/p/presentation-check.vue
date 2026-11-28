<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4_frccvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4_frccvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:presentation-check" /></template>
