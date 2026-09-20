<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecf832bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecf832bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-off" /></template>
