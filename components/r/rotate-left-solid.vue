<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hln_rnjqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hln_rnjqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:rotate-left-solid" /></template>
