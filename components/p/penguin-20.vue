<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l94gcsbcw.css';
import '../../css/m/m79wssnno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l94gcsbcw"/><path class="m79wssnno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penguin-20" /></template>
