<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajhzyebzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajhzyebzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:seek-forward-16" /></template>
