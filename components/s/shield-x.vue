<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tup9x39uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tup9x39uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-x" /></template>
