<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nihah-b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nihah-b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:panoramic-screen" /></template>
