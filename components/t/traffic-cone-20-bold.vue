<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaw8nnulj.css';
import '../../css/b/bpcftybjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vaw8nnulj"/><path class="bpcftybjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-cone-20-bold" /></template>
