<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9j4lbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9j4lbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-merge-cells" /></template>
