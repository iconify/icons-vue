<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-tunxbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-tunxbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:new-folder-flat" /></template>
