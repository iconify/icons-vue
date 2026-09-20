<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc1n2ug0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nc1n2ug0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maybe-dark" /></template>
