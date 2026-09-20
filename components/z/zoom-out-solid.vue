<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d72e7jb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d72e7jb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:zoom-out-solid" /></template>
