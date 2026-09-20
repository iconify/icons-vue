<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex6_f7bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex6_f7bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vauxhall" /></template>
