<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mou012obv.css';
import '../../css/o/ozw-6jbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mou012obv"/><path class="ozw-6jbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:shuffle-16" /></template>
