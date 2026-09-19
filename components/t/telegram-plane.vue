<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqkkvcsxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eqkkvcsxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:telegram-plane" /></template>
