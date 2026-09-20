<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf_46ablw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cf_46ablw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:radioactive-2-flat" /></template>
