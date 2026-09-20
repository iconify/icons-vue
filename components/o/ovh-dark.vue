<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdvn_thzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdvn_thzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovh-dark" /></template>
