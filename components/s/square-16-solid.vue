<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmz2nobkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vmz2nobkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:square-16-solid" /></template>
