<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdbhn9wpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mdbhn9wpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:panel-ipc-question" /></template>
