<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yavt59bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yavt59bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scion" /></template>
