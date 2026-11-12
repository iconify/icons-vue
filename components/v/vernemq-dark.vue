<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-bs936qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-bs936qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vernemq-dark" /></template>
