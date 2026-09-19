<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywvj5dbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ywvj5dbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:vaadin" /></template>
