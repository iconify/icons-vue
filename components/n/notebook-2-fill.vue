<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw5_q-bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw5_q-bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-2-fill" /></template>
