<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drnzps6if.css';
import '../../css/f/fifx41-ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drnzps6if"/><path class="fifx41-ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tablet-bold-duotone" /></template>
