<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okh3m0bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="okh3m0bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:phone-outline" /></template>
