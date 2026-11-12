<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk064txyy.css';
import '../../css/j/jz4ibqfjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="nk064txyy"/><path class="jz4ibqfjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:our-shopping-list-light" /></template>
