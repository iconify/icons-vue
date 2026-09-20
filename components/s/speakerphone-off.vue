<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og908q8dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og908q8dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speakerphone-off" /></template>
