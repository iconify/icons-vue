<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ellu3obxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ellu3obxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mouse-wireless-solid" /></template>
