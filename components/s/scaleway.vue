<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkqzanbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkqzanbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scaleway" /></template>
