<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs0ygwojm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cs0ygwojm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinkary-light" /></template>
