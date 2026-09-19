<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-mwivb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-mwivb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:trend-down-fill" /></template>
