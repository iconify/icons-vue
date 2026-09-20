<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h219x64vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h219x64vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pf2etools-dark" /></template>
