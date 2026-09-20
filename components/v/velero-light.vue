<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bht_f5brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bht_f5brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velero-light" /></template>
