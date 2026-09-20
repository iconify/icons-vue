<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u98efjc-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u98efjc-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:volume-control-warning-bold" /></template>
