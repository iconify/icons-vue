<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oicl4q_ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oicl4q_ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proval-light" /></template>
