<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbc3s20gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbc3s20gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:table-cells-split" /></template>
