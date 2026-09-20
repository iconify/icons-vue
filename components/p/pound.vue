<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4eq_ek3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4eq_ek3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:pound" /></template>
