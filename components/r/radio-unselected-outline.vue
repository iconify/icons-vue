<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trp_db72c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="trp_db72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:radio-unselected-outline" /></template>
