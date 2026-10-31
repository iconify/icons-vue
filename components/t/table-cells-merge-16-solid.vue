<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d79cnobuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d79cnobuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-merge-16-solid" /></template>
