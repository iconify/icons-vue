<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkpulpb9y.css';
import '../../css/g/gyakvvbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="gyakvvbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-right-20-bold" /></template>
