<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p220ddb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p220ddb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnform-dark" /></template>
