<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng093b3vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng093b3vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tick-03" /></template>
