<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj3bhgb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj3bhgb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minuspod-light" /></template>
