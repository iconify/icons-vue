<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f77o91b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f77o91b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:table-lamp" /></template>
