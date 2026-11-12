<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3bhubjjm.css';
import '../../css/k/ktli5dbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3bhubjjm"/><path class="ktli5dbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strapi-dark" /></template>
