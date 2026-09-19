<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edhpo_owh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="edhpo_owh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:music-score" /></template>
