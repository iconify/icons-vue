<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utcxkkbxw.css';
import '../../css/g/gtg_bmb_n.css';
import '../../css/t/t87_xhoos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utcxkkbxw"/><path class="gtg_bmb_n"/><path class="t87_xhoos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tree-20-bold" /></template>
