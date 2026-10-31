<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppmq00bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppmq00bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-left-filled" /></template>
