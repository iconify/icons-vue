<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od7kjibfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="od7kjibfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-folder" /></template>
