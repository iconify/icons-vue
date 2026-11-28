<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxgmkyps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvxgmkyps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:semaphore-horizontal-solid" /></template>
