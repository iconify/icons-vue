<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ci-rg2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0ci-rg2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:stats-down-alt" /></template>
