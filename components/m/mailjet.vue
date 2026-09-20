<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujux3-pap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujux3-pap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailjet" /></template>
