<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1-iiebzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="t1-iiebzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:online" /></template>
