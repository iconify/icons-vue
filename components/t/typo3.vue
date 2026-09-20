<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbnekz-ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbnekz-ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typo3" /></template>
