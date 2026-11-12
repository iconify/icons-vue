<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwgvggbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwgvggbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pent-no-light" /></template>
