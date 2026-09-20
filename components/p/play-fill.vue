<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjoczqjhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjoczqjhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:play-fill" /></template>
