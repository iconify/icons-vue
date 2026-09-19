<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7vz9wb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7vz9wb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:undo" /></template>
