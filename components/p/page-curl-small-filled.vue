<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0_gk4btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e0_gk4btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-curl-small-filled" /></template>
