<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve8ocsp6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ve8ocsp6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:taxi-front-fill" /></template>
