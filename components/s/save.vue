<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxn3gdbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lxn3gdbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:save" /></template>
