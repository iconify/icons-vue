<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9y34yaiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b9y34yaiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pencil-square-solid" /></template>
