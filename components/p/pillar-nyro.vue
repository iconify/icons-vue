<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4squf7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt4squf7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pillar-nyro" /></template>
