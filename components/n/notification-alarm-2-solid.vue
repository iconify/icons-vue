<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-xcio3ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-xcio3ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:notification-alarm-2-solid" /></template>
