<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgp1ggbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgp1ggbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remmina-light" /></template>
