<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m49ciubkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m49ciubkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:map" /></template>
