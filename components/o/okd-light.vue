<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr-i3_k_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cr-i3_k_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:okd-light" /></template>
