<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbq477g4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbq477g4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-round-outline" /></template>
