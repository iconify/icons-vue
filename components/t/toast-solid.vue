<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_a7tmmsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_a7tmmsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:toast-solid" /></template>
