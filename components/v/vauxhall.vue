<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va13wb4as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va13wb4as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vauxhall" /></template>
