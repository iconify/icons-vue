<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/druapyb0f.css';
import '../../css/p/psdm-j5hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="druapyb0f"/><path class="psdm-j5hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-storage-20-bold" /></template>
