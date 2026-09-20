<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrsiusmyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xrsiusmyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-left" /></template>
