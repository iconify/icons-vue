<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve_z1ti7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_z1ti7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:terminal-outline" /></template>
