<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezfwb2bob.css';
import '../../css/q/qvf68znnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ezfwb2bob"/><path class="qvf68znnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-copy" /></template>
