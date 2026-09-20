<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzdiky75l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzdiky75l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:phone-actions-refresh-bold" /></template>
