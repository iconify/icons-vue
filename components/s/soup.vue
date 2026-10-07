<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qumtwzh_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qumtwzh_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:soup" /></template>
