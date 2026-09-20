<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw_fdvb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kw_fdvb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:treasure-chest" /></template>
