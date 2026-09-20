<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu2hdnbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu2hdnbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:propane-tank" /></template>
