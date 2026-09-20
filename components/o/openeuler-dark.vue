<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzd74tzyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzd74tzyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openeuler-dark" /></template>
