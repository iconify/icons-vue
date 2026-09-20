<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4s5-6b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y4s5-6b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slotpoll-light" /></template>
