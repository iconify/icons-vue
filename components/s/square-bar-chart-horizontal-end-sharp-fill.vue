<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4zi-4u_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4zi-4u_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-horizontal-end-sharp-fill" /></template>
