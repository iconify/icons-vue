<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3k1rzixx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3k1rzixx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:npr-dark" /></template>
