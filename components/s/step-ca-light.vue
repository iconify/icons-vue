<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap7k5ib6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ap7k5ib6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:step-ca-light" /></template>
