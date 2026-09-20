<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scey3vbcr.css';
import '../../css/n/nutzz_b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="scey3vbcr"/><path clip-rule="evenodd" class="nutzz_b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:snapshot-16" /></template>
