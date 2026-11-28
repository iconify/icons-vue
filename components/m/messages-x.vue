<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzv9-9rfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzv9-9rfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:messages-x" /></template>
