<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht82qccml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ht82qccml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-bill-alt" /></template>
