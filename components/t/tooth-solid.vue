<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi-bp6xsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zi-bp6xsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tooth-solid" /></template>
