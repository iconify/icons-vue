<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_kg13bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_kg13bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shaarli-dark" /></template>
