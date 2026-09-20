<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlv355f2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlv355f2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo-switch-dark" /></template>
