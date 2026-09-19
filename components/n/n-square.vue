<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw8j__w4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="pw8j__w4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:n-square" /></template>
