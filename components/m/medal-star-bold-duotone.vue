<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxalaab1z.css';
import '../../css/y/yxo0gabyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxalaab1z"/><path clip-rule="evenodd" class="yxo0gabyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-bold-duotone" /></template>
