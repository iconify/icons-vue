<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9wqcob7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9wqcob7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-inc-cash" /></template>
