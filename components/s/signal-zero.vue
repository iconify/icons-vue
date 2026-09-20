<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc8-xabic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8-xabic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signal-zero" /></template>
