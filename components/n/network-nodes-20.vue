<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7_bml7xz.css';
import '../../css/k/kte3hjbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s7_bml7xz"/><path class="kte3hjbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:network-nodes-20" /></template>
