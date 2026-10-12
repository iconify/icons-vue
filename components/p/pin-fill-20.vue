<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9kybysey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9kybysey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-fill-20" /></template>
