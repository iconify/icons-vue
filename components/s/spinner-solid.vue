<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7u7tdb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t7u7tdb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spinner-solid" /></template>
