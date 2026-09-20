<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhyksccpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhyksccpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trend-arrow-down" /></template>
