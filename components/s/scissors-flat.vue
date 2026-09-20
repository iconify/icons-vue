<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0nycdcmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t0nycdcmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:scissors-flat" /></template>
