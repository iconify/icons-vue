<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrvc_wb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rrvc_wb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:merge-request" /></template>
