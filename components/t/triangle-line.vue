<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdi1o_bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdi1o_bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:triangle-line" /></template>
