<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irpyohboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="irpyohboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:rectangle-flag-solid" /></template>
