<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhj959bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhj959bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smart-home-check" /></template>
