<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1i2kqxtp.css';
import '../../css/z/zhydivsjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p1i2kqxtp"/><path class="zhydivsjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:note-48" /></template>
