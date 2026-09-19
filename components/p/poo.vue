<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qogcae2md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qogcae2md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:poo" /></template>
