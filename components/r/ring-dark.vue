<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-758iasb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-758iasb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ring-dark" /></template>
