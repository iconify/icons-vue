<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8j7ctm1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8j7ctm1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tf1" /></template>
