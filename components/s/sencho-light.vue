<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0l1cwbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x0l1cwbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sencho-light" /></template>
