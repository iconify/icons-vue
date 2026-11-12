<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lurj54bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lurj54bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:steam-dark" /></template>
