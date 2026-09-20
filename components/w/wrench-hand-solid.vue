<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghblb--5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ghblb--5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wrench-hand-solid" /></template>
