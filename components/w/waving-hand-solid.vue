<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aghqy4byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aghqy4byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:waving-hand-solid" /></template>
