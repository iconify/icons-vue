<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4qtrp1ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d4qtrp1ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:skull-2-solid" /></template>
