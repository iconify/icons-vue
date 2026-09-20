<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpiizxoqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpiizxoqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:windows" /></template>
