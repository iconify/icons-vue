<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu25hacoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eu25hacoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-edit-outline" /></template>
