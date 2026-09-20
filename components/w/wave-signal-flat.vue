<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3q9_5bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x3q9_5bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:wave-signal-flat" /></template>
