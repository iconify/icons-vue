<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x66e6iaec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x66e6iaec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:runtipi-dark" /></template>
