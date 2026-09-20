<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu3ov0u1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu3ov0u1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-dashboard-edit-outline" /></template>
