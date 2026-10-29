<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uryvlvbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uryvlvbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:table-cells-merge" /></template>
