<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz5jssbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz5jssbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tracking" /></template>
