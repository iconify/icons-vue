<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx6no8bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx6no8bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:road-sign-turn-left-bold" /></template>
