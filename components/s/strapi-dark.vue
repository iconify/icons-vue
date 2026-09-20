<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru_rc6bbb.css';
import '../../css/k/ktli5dbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru_rc6bbb"/><path class="ktli5dbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strapi-dark" /></template>
