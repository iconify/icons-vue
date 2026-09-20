<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12hh6b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x12hh6b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transfer-down" /></template>
