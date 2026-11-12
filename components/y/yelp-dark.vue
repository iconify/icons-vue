<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-efk4bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-efk4bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yelp-dark" /></template>
