<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhwbso37e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhwbso37e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification" /></template>
