<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtqxdlbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="dtqxdlbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:readernaut" /></template>
