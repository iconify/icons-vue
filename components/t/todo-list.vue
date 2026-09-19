<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wktbs6b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wktbs6b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:todo-list" /></template>
