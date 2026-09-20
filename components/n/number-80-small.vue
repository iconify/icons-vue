<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc7o19beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc7o19beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-80-small" /></template>
