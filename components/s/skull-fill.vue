<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb8v8tbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb8v8tbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skull-fill" /></template>
