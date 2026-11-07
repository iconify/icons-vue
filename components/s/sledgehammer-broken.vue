<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atj5g8h1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atj5g8h1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sledgehammer-broken" /></template>
