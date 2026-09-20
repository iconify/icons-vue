<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k__ujmbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k__ujmbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rails" /></template>
