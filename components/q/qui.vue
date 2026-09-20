<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabrn8b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mabrn8b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qui" /></template>
