<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb7dtlbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wb7dtlbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shoko-server-light" /></template>
