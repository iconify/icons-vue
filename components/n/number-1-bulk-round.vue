<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pya37j6aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pya37j6aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-1-bulk-round" /></template>
