<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1pkdl2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1pkdl2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sword" /></template>
