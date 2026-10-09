<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krxvcobsl.css';
import '../../css/c/c6dnn6b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="krxvcobsl"/><path class="c6dnn6b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-20-bold" /></template>
