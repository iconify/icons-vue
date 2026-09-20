<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pot-aq7pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pot-aq7pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-hexagon" /></template>
