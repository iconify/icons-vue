<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epd4lwbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="epd4lwbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:sidebar-left-16-solid" /></template>
