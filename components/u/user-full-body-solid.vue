<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_x16bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uw_x16bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:user-full-body-solid" /></template>
