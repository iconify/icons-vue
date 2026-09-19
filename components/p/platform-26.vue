<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyeofqbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="eyeofqbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:platform-26" /></template>
