<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmizg-b1r.css';
import '../../css/j/jzwe16sbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmizg-b1r"/><path class="jzwe16sbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sad-line" /></template>
