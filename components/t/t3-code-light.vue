<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtyf22b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vtyf22b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:t3-code-light" /></template>
