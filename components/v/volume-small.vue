<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a9vkbzg.css';
import '../../css/d/da1dlqbrp.css';
import '../../css/z/z_o_occeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="a0a9vkbzg"><path class="da1dlqbrp"/><path class="z_o_occeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:volume-small" /></template>
