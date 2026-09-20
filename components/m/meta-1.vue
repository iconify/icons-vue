<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz07o0bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="kz07o0bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:meta-1" /></template>
