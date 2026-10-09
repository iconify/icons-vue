<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so2mw5bhs.css';
import '../../css/n/nnuycobpf.css';
import '../../css/n/ney70wbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="so2mw5bhs"/><path class="nnuycobpf"/><path class="ney70wbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-river-20-bold" /></template>
