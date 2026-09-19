<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1cisd-qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1cisd-qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-living" /></template>
