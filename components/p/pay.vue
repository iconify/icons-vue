<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbkf4vbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cbkf4vbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pay" /></template>
