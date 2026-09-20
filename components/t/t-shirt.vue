<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_wdvtgci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_wdvtgci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:t-shirt" /></template>
