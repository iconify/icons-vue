<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv0lc4yqq.css';
import '../../css/v/vi98df-3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv0lc4yqq"/><path class="vi98df-3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:statamic-light" /></template>
