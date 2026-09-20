<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2rt8rbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z2rt8rbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:party-popper-remix" /></template>
