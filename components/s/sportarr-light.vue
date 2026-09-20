<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv_2wekjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bv_2wekjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sportarr-light" /></template>
