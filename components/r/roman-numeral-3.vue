<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1m9nwbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1m9nwbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-3" /></template>
