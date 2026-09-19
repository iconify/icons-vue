<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymiftcbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymiftcbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pendant-long-up" /></template>
