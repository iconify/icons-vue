<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8l9hqbrf.css';
import '../../css/n/nz0jllbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k8l9hqbrf"/><path class="nz0jllbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:saltcorn-light" /></template>
