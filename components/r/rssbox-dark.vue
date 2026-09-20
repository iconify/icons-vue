<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaknvpb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xaknvpb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rssbox-dark" /></template>
