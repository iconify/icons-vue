<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl4d36m1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl4d36m1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-dining" /></template>
