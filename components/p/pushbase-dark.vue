<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3hwbm_6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3hwbm_6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pushbase-dark" /></template>
