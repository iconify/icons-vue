<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf1mcybca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cf1mcybca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:mask-16-solid" /></template>
