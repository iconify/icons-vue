<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvx5yfbep.css';
import '../../css/t/t91s7oy2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hvx5yfbep"/><path class="t91s7oy2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:x-circle" /></template>
