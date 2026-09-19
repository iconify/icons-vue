<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kevxtbbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kevxtbbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ndepend" /></template>
