<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7ms5bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="lu7ms5bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:minus-square" /></template>
