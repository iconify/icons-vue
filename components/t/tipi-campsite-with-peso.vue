<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unru5tbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="unru5tbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tipi-campsite-with-peso" /></template>
