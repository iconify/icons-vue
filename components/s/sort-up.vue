<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8tmysb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8tmysb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sort-up" /></template>
