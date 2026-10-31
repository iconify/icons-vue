<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq1ge0_ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq1ge0_ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-21-9-fill-round" /></template>
