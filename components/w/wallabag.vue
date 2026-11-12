<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecn1w4bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ecn1w4bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wallabag" /></template>
