<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz_n-fbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz_n-fbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:prism-outline" /></template>
