<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntktdbcmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ntktdbcmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:minus-circle-outline" /></template>
