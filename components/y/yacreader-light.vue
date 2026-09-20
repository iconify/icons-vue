<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptw17bc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptw17bc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yacreader-light" /></template>
