<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uctb9sbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uctb9sbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-bulk-round" /></template>
