<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etaycyb8r.css';
import '../../css/y/yd56p_bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="etaycyb8r"/><circle class="yd56p_bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:paw" /></template>
