<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjg6q_bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":384};
const content = `<path class="kjg6q_bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:volume-down" /></template>
