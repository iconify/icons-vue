<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhg4t7bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhg4t7bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rustdesk-light" /></template>
