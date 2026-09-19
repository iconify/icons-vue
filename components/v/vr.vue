<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxuje6u-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nxuje6u-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:vr" /></template>
