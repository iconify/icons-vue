<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opky82g8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opky82g8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paw" /></template>
