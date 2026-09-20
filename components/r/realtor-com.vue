<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z00tr3bse.css';
import '../../css/i/i8n-k03nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z00tr3bse"/><path class="i8n-k03nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:realtor-com" /></template>
