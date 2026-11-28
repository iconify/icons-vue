<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzckph18p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzckph18p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ship-wheel-solid" /></template>
