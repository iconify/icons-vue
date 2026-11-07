<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvlkclb-m.css';
import '../../css/q/qbcnl7b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvlkclb-m"/><path class="qbcnl7b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-low-outline" /></template>
