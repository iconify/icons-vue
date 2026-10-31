<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o10psrw2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o10psrw2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-open-fill-round" /></template>
