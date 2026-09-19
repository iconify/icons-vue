<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntuotyc_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ntuotyc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-speaker-fill-12" /></template>
