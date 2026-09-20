<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w848efbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w848efbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:moustache-flat" /></template>
