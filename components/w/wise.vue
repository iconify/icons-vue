<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsrignk3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsrignk3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wise" /></template>
