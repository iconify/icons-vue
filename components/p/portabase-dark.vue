<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-zau8bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-zau8bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portabase-dark" /></template>
