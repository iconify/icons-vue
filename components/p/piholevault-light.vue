<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8fz_zm9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8fz_zm9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piholevault-light" /></template>
