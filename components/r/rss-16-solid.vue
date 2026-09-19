<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scdc07bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="scdc07bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rss-16-solid" /></template>
