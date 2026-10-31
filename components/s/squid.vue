<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le9u54-7e.css';
import '../../css/t/t4fmldbqy.css';
import '../../css/z/zoa_b5bnt.css';
import '../../css/s/slrtfiplt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="le9u54-7e"/><path class="t4fmldbqy"/><path class="zoa_b5bnt"/><path class="slrtfiplt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:squid" /></template>
