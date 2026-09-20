<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2ou5m2vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ou5m2vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-10-box" /></template>
