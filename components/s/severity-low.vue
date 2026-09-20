<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygepkbb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="ygepkbb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:severity-low" /></template>
