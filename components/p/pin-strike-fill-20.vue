<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gat3x6vgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gat3x6vgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-strike-fill-20" /></template>
