<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvgr2srcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pvgr2srcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:toilet-sign-man-woman-2-flat" /></template>
