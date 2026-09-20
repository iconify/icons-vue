<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5fu5bc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q5fu5bc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:piggy-bank-solid" /></template>
