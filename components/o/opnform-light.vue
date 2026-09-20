<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtdy76u6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtdy76u6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnform-light" /></template>
