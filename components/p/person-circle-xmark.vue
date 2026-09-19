<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxr-42qbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nxr-42qbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-circle-xmark" /></template>
