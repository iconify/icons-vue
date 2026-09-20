<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyd79ccra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oyd79ccra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:positive-intentions-dark" /></template>
