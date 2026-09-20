<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-f-yb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-f-yb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xbox-controller-battery-low" /></template>
