<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r48o9ebhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r48o9ebhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t-mobile-dark" /></template>
