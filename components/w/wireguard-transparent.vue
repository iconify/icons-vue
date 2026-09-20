<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiikn06-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tiikn06-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wireguard-transparent" /></template>
