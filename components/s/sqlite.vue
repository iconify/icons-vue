<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxptrhd-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":458,"height":512};
const content = `<path class="pxptrhd-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sqlite" /></template>
