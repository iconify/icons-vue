<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr-zs8cga.css';
import '../../css/o/ooobm-34o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tr-zs8cga"/><path class="ooobm-34o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:turtle-20-bold" /></template>
