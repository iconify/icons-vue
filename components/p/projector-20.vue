<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi3_jwkbn.css';
import '../../css/z/zklarom7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mi3_jwkbn"/><path class="zklarom7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:projector-20" /></template>
