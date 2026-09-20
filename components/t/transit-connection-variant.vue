<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd8xxabva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd8xxabva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transit-connection-variant" /></template>
