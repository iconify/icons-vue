<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urpzf1b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="urpzf1b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:notepad-text-solid" /></template>
