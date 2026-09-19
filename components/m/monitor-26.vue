<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo8rj3gpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qo8rj3gpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:monitor-26" /></template>
