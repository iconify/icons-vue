<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q69jhsbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q69jhsbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-square" /></template>
