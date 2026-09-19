<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngdodkbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ngdodkbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-off-fill-16" /></template>
