<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl888_buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl888_buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:send" /></template>
