<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oobt_dbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oobt_dbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shapes-48" /></template>
