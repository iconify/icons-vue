<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agm_q7boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="agm_q7boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:scala-16" /></template>
