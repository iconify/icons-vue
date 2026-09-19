<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw2fmneoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1472};
const content = `<path class="pw2fmneoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:user-waiter-female" /></template>
