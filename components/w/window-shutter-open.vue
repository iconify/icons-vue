<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sca9mvbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sca9mvbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:window-shutter-open" /></template>
