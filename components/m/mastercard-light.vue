<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epykl_-yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epykl_-yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mastercard-light" /></template>
