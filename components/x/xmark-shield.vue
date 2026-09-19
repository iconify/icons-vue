<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpg_u0oym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kpg_u0oym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-shield" /></template>
