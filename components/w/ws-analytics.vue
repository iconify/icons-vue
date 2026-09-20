<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd0mncbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kd0mncbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ws-analytics" /></template>
