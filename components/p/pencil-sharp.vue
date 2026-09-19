<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvgfvo2if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvgfvo2if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pencil-sharp" /></template>
