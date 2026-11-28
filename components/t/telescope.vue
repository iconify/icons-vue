<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_mia5z_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_mia5z_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:telescope" /></template>
