<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anms5nb2o.css';
import '../../css/e/epn6lpbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anms5nb2o"/><path class="epn6lpbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:people-circle-outline" /></template>
