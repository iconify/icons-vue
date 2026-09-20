<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkqw-6hkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkqw-6hkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unimus-light" /></template>
