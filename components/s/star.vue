<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu19h5b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hu19h5b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:star" /></template>
