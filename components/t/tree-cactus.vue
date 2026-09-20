<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnt0b3bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qnt0b3bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-cactus" /></template>
