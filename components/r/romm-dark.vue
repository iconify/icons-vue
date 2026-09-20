<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v12ih4bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v12ih4bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romm-dark" /></template>
