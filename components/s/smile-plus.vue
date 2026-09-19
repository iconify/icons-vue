<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n09tnb1bj.css';
import '../../css/e/ekil0t11d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n09tnb1bj"/><path class="ekil0t11d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:smile-plus" /></template>
