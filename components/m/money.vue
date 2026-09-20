<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiv55sryd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aiv55sryd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:money" /></template>
