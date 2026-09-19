<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmik2abzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kmik2abzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:whatsapp" /></template>
