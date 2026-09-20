<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtvc137bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtvc137bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zaneops-dark" /></template>
