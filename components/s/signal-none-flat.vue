<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twl58-cvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="twl58-cvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:signal-none-flat" /></template>
