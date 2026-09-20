<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lksscjg4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lksscjg4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rusta-light" /></template>
