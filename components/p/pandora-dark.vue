<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngnqm6b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngnqm6b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pandora-dark" /></template>
