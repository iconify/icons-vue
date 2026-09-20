<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s14l_k1mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s14l_k1mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:waning-cresent-moon-flat" /></template>
