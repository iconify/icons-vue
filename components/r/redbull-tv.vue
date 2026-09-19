<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btq24pwml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btq24pwml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:redbull-tv" /></template>
