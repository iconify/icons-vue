<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5sk9tbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5sk9tbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-list-outline" /></template>
