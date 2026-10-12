<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akn59mbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="akn59mbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-stroke-20" /></template>
