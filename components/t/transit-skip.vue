<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spszvlbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spszvlbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transit-skip" /></template>
