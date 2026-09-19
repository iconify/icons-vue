<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo2nb0bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lo2nb0bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nant" /></template>
