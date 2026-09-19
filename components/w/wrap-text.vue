<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7g2i_2hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7g2i_2hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:wrap-text" /></template>
