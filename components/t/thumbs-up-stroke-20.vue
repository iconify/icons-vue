<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv1dmxb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qv1dmxb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:thumbs-up-stroke-20" /></template>
