<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m80-xcc1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m80-xcc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:table-cells-merge" /></template>
