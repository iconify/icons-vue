<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbnoic5rd.css';
import '../../css/m/m-8nc9b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lbnoic5rd"/><path class="m-8nc9b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:save-20" /></template>
