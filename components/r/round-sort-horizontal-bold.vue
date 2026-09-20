<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdqm6cbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdqm6cbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-sort-horizontal-bold" /></template>
