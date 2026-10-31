<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4h4q_bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4h4q_bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-down-left-16-solid" /></template>
