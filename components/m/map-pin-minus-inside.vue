<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfvx0vbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfvx0vbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-minus-inside" /></template>
