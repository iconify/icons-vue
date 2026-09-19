<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z62-w0m7e.css';
import '../../css/l/l47wg2bol.css';
import '../../css/m/mubrohbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z62-w0m7e"/><path class="l47wg2bol"/><path class="mubrohbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rainbow" /></template>
