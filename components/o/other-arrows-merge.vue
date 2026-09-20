<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohjefuxdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ohjefuxdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-arrows-merge" /></template>
