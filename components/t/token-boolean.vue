<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4ca_8blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t4ca_8blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-boolean" /></template>
