<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx-rucm_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hx-rucm_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trackly-dark" /></template>
