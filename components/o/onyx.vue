<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91ua3bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o91ua3bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onyx" /></template>
