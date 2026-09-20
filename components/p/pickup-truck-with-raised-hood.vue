<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkn6dvbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nkn6dvbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pickup-truck-with-raised-hood" /></template>
