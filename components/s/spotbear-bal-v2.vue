<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzmf56btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzmf56btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotbear-bal-v2" /></template>
