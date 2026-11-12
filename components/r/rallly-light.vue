<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0sj-8bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d0sj-8bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rallly-light" /></template>
