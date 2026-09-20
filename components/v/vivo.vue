<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6ef6w-6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6ef6w-6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vivo" /></template>
