<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nen5y7buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nen5y7buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:minima" /></template>
