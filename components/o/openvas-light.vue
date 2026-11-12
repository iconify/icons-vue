<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz9i9u2gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uz9i9u2gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openvas-light" /></template>
