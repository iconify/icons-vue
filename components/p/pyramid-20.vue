<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ei9-u4f.css';
import '../../css/t/trjhecjvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v7ei9-u4f"/><path class="trjhecjvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pyramid-20" /></template>
