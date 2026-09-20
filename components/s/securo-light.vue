<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcdh9_b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bcdh9_b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:securo-light" /></template>
