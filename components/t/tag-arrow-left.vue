<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqd3_w6nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="eqd3_w6nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-arrow-left" /></template>
