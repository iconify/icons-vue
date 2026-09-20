<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m76gx5b6o.css';
import '../../css/l/ll5nhre1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="m76gx5b6o"/><path class="ll5nhre1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:small-orange-diamond" /></template>
