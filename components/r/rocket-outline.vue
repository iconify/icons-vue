<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw55_xb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw55_xb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rocket-outline" /></template>
