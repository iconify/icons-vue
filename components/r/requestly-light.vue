<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9lsb3wir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9lsb3wir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:requestly-light" /></template>
