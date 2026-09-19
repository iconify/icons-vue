<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iejg9x5ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iejg9x5ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-build" /></template>
