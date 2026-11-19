<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khnqrjkad.css';
import '../../css/u/ukv9p-tgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="khnqrjkad"/><path class="ukv9p-tgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mongodb-wordmark" /></template>
