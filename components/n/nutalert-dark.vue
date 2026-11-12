<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moufh4n1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moufh4n1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nutalert-dark" /></template>
