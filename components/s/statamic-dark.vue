<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_saacsa.css';
import '../../css/k/kaqsw12py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kc_saacsa"/><path class="kaqsw12py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:statamic-dark" /></template>
