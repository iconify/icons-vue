<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/engaw8bgi.css';
import '../../css/l/lsh_8pjho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="engaw8bgi"/><path class="lsh_8pjho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-pig-48-bold" /></template>
