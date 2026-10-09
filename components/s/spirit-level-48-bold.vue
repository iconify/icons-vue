<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hda2nzbnb.css';
import '../../css/z/zodp_k1_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hda2nzbnb"/><path class="zodp_k1_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spirit-level-48-bold" /></template>
