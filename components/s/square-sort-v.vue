<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w85o7zb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w85o7zb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-sort-v" /></template>
