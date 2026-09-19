<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw03xnjge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mw03xnjge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:medal" /></template>
