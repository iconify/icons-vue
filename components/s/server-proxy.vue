<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyr___g3f.css';
import '../../css/d/dfv392bxj.css';
import '../../css/g/g03t4bb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wyr___g3f"/><circle class="dfv392bxj"/><path class="g03t4bb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:server-proxy" /></template>
