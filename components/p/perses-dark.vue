<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oawho9b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oawho9b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:perses-dark" /></template>
