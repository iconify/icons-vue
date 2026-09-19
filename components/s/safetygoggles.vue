<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlyg48kvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":614};
const content = `<path class="hlyg48kvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:safetygoggles" /></template>
