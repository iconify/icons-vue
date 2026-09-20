<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8fwj6jpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8fwj6jpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:palette-advanced" /></template>
