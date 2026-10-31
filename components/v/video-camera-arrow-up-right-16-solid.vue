<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzdv_vtcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bzdv_vtcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-up-right-16-solid" /></template>
