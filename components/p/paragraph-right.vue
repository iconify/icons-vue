<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmsa-7c1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rmsa-7c1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:paragraph-right" /></template>
