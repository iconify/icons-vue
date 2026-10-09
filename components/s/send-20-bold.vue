<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z63nbsbdb.css';
import '../../css/h/hjq60mx9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z63nbsbdb"/><path class="hjq60mx9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-20-bold" /></template>
