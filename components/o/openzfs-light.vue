<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf_9k6b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sf_9k6b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openzfs-light" /></template>
