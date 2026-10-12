<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv0u75bem.css';
import '../../css/z/zplth4i-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xv0u75bem"/><path class="zplth4i-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-x-stroke-20" /></template>
