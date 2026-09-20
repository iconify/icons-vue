<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8-o6bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="es8-o6bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-squatting-and-person-reaching-up" /></template>
