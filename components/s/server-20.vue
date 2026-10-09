<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eab-bra5j.css';
import '../../css/e/eokgyxb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eab-bra5j"/><path class="eokgyxb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-20" /></template>
