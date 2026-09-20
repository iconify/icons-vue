<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su36muyou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su36muyou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidero-light" /></template>
