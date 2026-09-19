<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl308zt5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rl308zt5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:toilet-paper-slash" /></template>
