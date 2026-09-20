<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6d7y2btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6d7y2btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:no-gas-station-bold" /></template>
