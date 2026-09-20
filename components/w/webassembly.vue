<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eru_cbbks.css';
import '../../css/g/gnuh1n3mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eru_cbbks"/><path class="gnuh1n3mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:webassembly" /></template>
