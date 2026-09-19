<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmtbpb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="itmtbpb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:octagon" /></template>
