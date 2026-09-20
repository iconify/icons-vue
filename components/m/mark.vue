<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkt6a0beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dkt6a0beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:mark" /></template>
