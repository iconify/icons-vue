<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpotc5b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wpotc5b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:trash" /></template>
