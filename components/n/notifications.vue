<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osa9y-bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="osa9y-bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications" /></template>
