<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sra7u5brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sra7u5brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:webcam-off-solid" /></template>
