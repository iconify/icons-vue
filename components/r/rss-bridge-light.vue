<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efumexbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="efumexbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rss-bridge-light" /></template>
