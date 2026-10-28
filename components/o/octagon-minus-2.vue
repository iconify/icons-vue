<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noagkzbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noagkzbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-minus-2" /></template>
