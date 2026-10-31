<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r20pbs6eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r20pbs6eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-fill-round" /></template>
