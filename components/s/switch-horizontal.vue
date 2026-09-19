<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snw4uebvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="snw4uebvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:switch-horizontal" /></template>
