<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig39blqsl.css';
import '../../css/t/tx633bbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ig39blqsl"/><path class="tx633bbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pyramid-20-bold" /></template>
