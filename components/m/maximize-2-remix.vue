<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-qb_bq7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p-qb_bq7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:maximize-2-remix" /></template>
