<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnb6j5bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnb6j5bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-5-fill" /></template>
