<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzag0q2pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vzag0q2pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pytest" /></template>
