<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j753kt9-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="j753kt9-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sports" /></template>
