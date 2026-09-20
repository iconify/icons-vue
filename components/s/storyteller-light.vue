<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frshv9b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frshv9b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyteller-light" /></template>
