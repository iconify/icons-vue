<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxjbxrbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nxjbxrbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-circle-arrow-down-filled" /></template>
