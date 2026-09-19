<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5_ntkb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5_ntkb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:panorama-horizontal" /></template>
