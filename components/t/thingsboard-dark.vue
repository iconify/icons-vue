<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im5kk3zjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im5kk3zjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingsboard-dark" /></template>
