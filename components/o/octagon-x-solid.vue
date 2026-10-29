<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxs67wbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxs67wbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:octagon-x-solid" /></template>
