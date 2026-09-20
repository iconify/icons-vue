<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz5j96neh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uz5j96neh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rocky-linux-light" /></template>
