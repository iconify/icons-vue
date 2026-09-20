<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp6avsbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp6avsbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wiper-fill" /></template>
