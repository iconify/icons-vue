<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybmo5mmpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybmo5mmpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-outline" /></template>
