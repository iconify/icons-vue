<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhtg36b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhtg36b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pie-chart-02" /></template>
