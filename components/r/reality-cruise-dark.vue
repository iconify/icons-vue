<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkw_0_bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkw_0_bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reality-cruise-dark" /></template>
