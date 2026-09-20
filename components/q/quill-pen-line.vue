<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx8t_pbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx8t_pbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quill-pen-line" /></template>
