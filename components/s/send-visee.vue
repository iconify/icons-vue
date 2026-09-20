<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1mi8z8gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1mi8z8gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:send-visee" /></template>
