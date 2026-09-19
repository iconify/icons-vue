<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afuem_b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afuem_b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-staircase" /></template>
