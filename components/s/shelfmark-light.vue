<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7rvs6pjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7rvs6pjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shelfmark-light" /></template>
