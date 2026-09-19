<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-45ogmcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q-45ogmcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mft" /></template>
