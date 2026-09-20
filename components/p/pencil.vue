<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giw_6scvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="giw_6scvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:pencil" /></template>
