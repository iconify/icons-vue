<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfwo_dbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nfwo_dbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-in-front-image" /></template>
