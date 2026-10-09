<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pek7vnbxc.css';
import '../../css/y/ywj7khc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pek7vnbxc"/><path class="ywj7khc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whistle-48" /></template>
