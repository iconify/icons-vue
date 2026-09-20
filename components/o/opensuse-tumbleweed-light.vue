<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib6mbs-7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib6mbs-7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-tumbleweed-light" /></template>
