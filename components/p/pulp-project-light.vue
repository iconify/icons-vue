<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcc6e0kab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcc6e0kab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulp-project-light" /></template>
