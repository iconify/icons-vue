<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk67zg56m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk67zg56m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:medal4-filled" /></template>
