<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snpnsac5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="snpnsac5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:umbrelos" /></template>
