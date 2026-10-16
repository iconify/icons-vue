<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai5j-lbxc.css';
import '../../css/m/mo6avcbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ai5j-lbxc"/><path class="mo6avcbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-low-20-bold" /></template>
