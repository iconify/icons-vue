<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokabookt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qokabookt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-location" /></template>
