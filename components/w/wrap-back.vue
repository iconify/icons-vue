<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/h/hsj4o8rgo.css';
import '../../css/l/lkbg2fbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="hsj4o8rgo"/><path class="lkbg2fbgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:wrap-back" /></template>
