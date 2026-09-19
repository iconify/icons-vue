<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jql1cebqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jql1cebqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vial-virus" /></template>
