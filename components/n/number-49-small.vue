<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/revk5vbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="revk5vbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-49-small" /></template>
