<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdkv85ljh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdkv85ljh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tape-measure" /></template>
