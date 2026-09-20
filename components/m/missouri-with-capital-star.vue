<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqtx79bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mqtx79bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:missouri-with-capital-star" /></template>
