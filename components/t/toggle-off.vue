<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8esq-gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qj8esq-gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:toggle-off" /></template>
