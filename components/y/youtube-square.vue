<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ulcowzu.css';
import '../../css/e/en0k_qb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_ulcowzu"/><path class="en0k_qb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:youtube-square" /></template>
