<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni999veso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni999veso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-check" /></template>
