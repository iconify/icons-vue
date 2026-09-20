<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3l6mhb4c.css';
import '../../css/q/qoes-qt6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3l6mhb4c"/><path class="qoes-qt6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:monetization-tablet-bold" /></template>
