<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_hsdf3i.css';
import '../../css/z/zfb6-85zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ha_hsdf3i"/><path clip-rule="evenodd" class="zfb6-85zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:print-preview-16" /></template>
