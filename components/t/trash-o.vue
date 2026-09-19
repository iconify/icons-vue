<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_30unbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1536};
const content = `<path class="t_30unbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:trash-o" /></template>
