<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkk6r5bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hkk6r5bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyteller-dark" /></template>
