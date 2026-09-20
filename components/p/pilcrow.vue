<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnqeyv27b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnqeyv27b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow" /></template>
