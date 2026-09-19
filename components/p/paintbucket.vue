<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkend5bbc.css';
import '../../css/o/o0czmk70w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkend5bbc"/><path class="o0czmk70w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:paintbucket" /></template>
