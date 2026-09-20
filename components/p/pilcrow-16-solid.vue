<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bde7xsbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bde7xsbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pilcrow-16-solid" /></template>
