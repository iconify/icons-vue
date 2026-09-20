<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz5zrpbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jz5zrpbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:width" /></template>
