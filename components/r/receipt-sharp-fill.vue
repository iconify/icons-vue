<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfii3za8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfii3za8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:receipt-sharp-fill" /></template>
