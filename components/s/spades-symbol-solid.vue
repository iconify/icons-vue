<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sewv9lb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sewv9lb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spades-symbol-solid" /></template>
