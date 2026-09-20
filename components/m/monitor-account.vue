<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvq8vlbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvq8vlbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-account" /></template>
