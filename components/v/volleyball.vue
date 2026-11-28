<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebxlwqd-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebxlwqd-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:volleyball" /></template>
