<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qasfav3td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qasfav3td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:train-lightrail-front" /></template>
