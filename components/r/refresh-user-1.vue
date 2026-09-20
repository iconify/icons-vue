<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ot-3wmv.css';
import '../../css/r/rbkemp0fh.css';
import '../../css/h/h8ov3rb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="y4ot-3wmv"/><path class="rbkemp0fh"/><path clip-rule="evenodd" class="h8ov3rb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:refresh-user-1" /></template>
