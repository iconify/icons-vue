<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbjc0y-xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjc0y-xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tplink-router" /></template>
