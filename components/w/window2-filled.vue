<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8r2gdb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8r2gdb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:window2-filled" /></template>
