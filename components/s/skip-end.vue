<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szgw_9b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="szgw_9b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-end" /></template>
