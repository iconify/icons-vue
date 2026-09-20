<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le9zsubzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le9zsubzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:natural-disaster-hurricane-bold" /></template>
