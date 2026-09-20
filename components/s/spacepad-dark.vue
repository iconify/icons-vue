<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vey5eii8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vey5eii8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spacepad-dark" /></template>
