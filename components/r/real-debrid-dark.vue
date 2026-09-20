<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kucghu1pp.css';
import '../../css/v/v3bumgb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kucghu1pp"/><path class="v3bumgb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:real-debrid-dark" /></template>
