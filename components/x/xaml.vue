<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aef3ixbes.css';
import '../../css/c/c2c3p-b5s.css';
import '../../css/z/zm33ygepl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aef3ixbes"/><path class="c2c3p-b5s"/><path class="zm33ygepl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:xaml" /></template>
