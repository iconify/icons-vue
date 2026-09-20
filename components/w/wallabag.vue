<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgmccfbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgmccfbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wallabag" /></template>
