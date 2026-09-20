<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75qm4lmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q75qm4lmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:play-list-4-solid" /></template>
